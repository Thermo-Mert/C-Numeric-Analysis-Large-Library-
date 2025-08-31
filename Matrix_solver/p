/*--------------------------------*- C++ -*----------------------------------*\
| solids4foam: solid mechanics and fluid-solid interaction simulations        |
| Version:     v2.0                                                           |
| Web:         https://solids4foam.github.io                                  |
| Disclaimer:  This offering is not approved or endorsed by OpenCFD Limited,  |
|              producer and distributor of the OpenFOAM software via          |
|              www.openfoam.com, and owner of the OPENFOAM® and OpenCFD®      |
|              trade marks.                                                   |
\*---------------------------------------------------------------------------*/
FoamFile
{
    version     2.0;
    format      ascii;
    class       volScalarField;
    object      p;
}
// * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * //

dimensions      [0 2 -2 0 0 0 0];

internalField   uniform 0;

boundaryField
{
   
      outlet
    {
         type fixedValue;
        value uniform 0;
    }
    inlet
    {
       type zeroGradient;
        value uniform 0;
    }
     fluid_wall
    {
        type zeroGradient;
        value uniform 0;
    }
     default_wall
    {
         type zeroGradient;
        value uniform 0;
    }
    fluidinner_wall
    {
        type zeroGradient;
        value uniform 0;
    }
    
    frontAndBackPlanes
    {
        type            empty;
    }



   
   
}

// ************************************************************************* //
