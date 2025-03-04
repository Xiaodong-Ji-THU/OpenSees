#==============================================================================
# 
#        OpenSees -- Open System For Earthquake Engineering Simulation
#                Pacific Earthquake Engineering Research Center
#
#==============================================================================

target_sources(OPS_Material
    PRIVATE
      AxialSp.cpp
      AxialSp.cpp
      AxialSpHD.cpp
      BWBN.cpp
      Bilin.cpp
      Bilin02.cpp

      ConcreteCM.cpp
      ConcreteD.cpp
      ConcretewBeta.cpp

      Elastic2Material.cpp
      ElasticBilin.cpp
      ElasticMaterial.cpp
      ElasticMultiLinear.cpp
      ElasticPPMaterial.cpp
      ElasticPowerFunc.cpp

      IMKBilin.cpp
      IMKPeakOriented.cpp
      IMKPinching.cpp

      MaterialState.cpp
      OriginCentered.cpp
      ParallelMaterial.cpp
      ResilienceLow.cpp
      Steel2.cpp
      SteelMPF.cpp
      SteelDRC.cpp      
      UVCuniaxial.cpp
      UniaxialMaterial.cpp
      #TclDegradingUniaxial.cpp
    PUBLIC
      AxialSp.h
      AxialSp.h
      AxialSpHD.h
      BWBN.h
      Bilin.h
      Bilin02.h

      ConcreteCM.h
      ConcreteD.h
      ConcretewBeta.h

      Elastic2Material.h
      ElasticBilin.h
      ElasticMaterial.h
      ElasticMultiLinear.h
      ElasticPPMaterial.h
      ElasticPowerFunc.h

      IMKBilin.h
      IMKPeakOriented.h
      IMKPinching.h

      MaterialState.h
      OriginCentered.h
      ParallelMaterial.h
      ResilienceLow.h
      Steel2.h
      SteelMPF.h
      SteelDRC.h      
      UVCuniaxial.h
      UniaxialMaterial.h
)


target_sources(OPS_Material
    PRIVATE
      ASD_SMA_3K.cpp
      BackboneMaterial.cpp
      BarSlipMaterial.cpp
      BilinearOilDamper.cpp
      Bond_SP01.cpp
      BoucWenMaterial.cpp
      BoucWenOriginal.cpp
      CFSSSWP.cpp
      CFSWSWP.cpp
      CableMaterial.cpp
      Cast.cpp
      Concrete01.cpp
      Concrete01WithSITC.cpp
      Concrete02.cpp
      Concrete02IS.cpp
      Concrete02Thermal.cpp
      Concrete04.cpp
      Concrete05.cpp
      Concrete06.cpp
      Concrete07.cpp
      ConcreteECThermal.cpp
      ConcreteSakaiKawashima.cpp
      ConcretewBeta.cpp
      ConfinedConcrete01.cpp
      ContinuumUniaxial.cpp
      CubicSpline.cpp
      DamperMaterial.cpp
      DegradingPinchedBW.cpp
      DoddRestr.cpp
      Dodd_Restrepo.cpp
      DrainMaterial.cpp
      ECC01.cpp
      ENTMaterial.cpp
      EPPGapMaterial.cpp
      ElasticBDMaterial.cpp
      ElasticMaterialThermal.cpp
      FRPConfinedConcrete.cpp
      FRPConfinedConcrete02.cpp
      FatigueMaterial.cpp
      #FedeasMaterial.cpp
      GNGMaterial.cpp
      HardeningMaterial.cpp
      #HardeningMaterial2.cpp
      HookGap.cpp
      HyperbolicGapMaterial.cpp
      HystereticMaterial.cpp
      HystereticPoly.cpp
      ImpactMaterial.cpp
      InitStrainMaterial.cpp
      InitStressMaterial.cpp
      KikuchiAikenHDR.cpp
      KikuchiAikenLRB.cpp
      Maxwell.cpp                      # Uses ops_Dt
      MinMaxMaterial.cpp
      ModIMKPeakOriented.cpp
      ModIMKPeakOriented02.cpp
      ModIMKPinching.cpp
      ModIMKPinching02.cpp
      MultiLinear.cpp
      Neoprene.cpp
      OOHystereticMaterial.cpp
      PathIndependentMaterial.cpp
      Pinching4Material.cpp
      PrestressedSteelMaterial.cpp
      RambergOsgoodSteel.cpp
      ReinforcingSteel.cpp
      ResilienceMaterialHR.cpp
      SAWSMaterial.cpp
      SPSW02.cpp
      SecantConcrete.cpp
      SelfCenteringMaterial.cpp
      SeriesMaterial.cpp
      ShearPanelMaterial.cpp
      SimpleFractureMaterial.cpp
      SLModel.cpp
      SmoothPSConcrete.cpp
      StainlessECThermal.cpp
      Steel01.cpp
      Steel01Thermal.cpp
      Steel02.cpp
      Steel02Fatigue.cpp
      Steel02Thermal.cpp
      Steel03.cpp
      Steel4.cpp
      SteelBRB.cpp
      SteelECThermal.cpp
      SteelFractureDI.cpp
      SteelMP.cpp
      TDConcrete.cpp
      TDConcreteEXP.cpp
      TDConcreteMC10.cpp
      TDConcreteMC10NL.cpp
      TensionOnlyMaterial.cpp
      UniaxialJ2Plasticity.cpp
      ViscousDamper.cpp
      ViscousMaterial.cpp
      WrapperUniaxialMaterial.cpp
      pyUCLA.cpp
      SMAMaterial.cpp
      
      TriMatrix.cpp

    PUBLIC
      ASD_SMA_3K.h
      BackboneMaterial.h
      BarSlipMaterial.h
      BilinearOilDamper.h
      Bond_SP01.h
      BoucWenMaterial.h
      BoucWenOriginal.h
      CFSSSWP.h
      CFSWSWP.h
      CableMaterial.h
      Cast.h
      Concrete01.h
      Concrete01WithSITC.h
      Concrete02.h
      Concrete02IS.h
      Concrete02Thermal.h
      Concrete04.h
      Concrete05.h
      Concrete06.h
      Concrete07.h
      ConcreteECThermal.h
      ConcreteSakaiKawashima.h
      ConcretewBeta.h
      ConfinedConcrete01.h
      ContinuumUniaxial.h
      CubicSpline.h
      DamperMaterial.h
      DegradingPinchedBW.h
      DoddRestr.h
      Dodd_Restrepo.h
      DrainMaterial.h
      ECC01.h
      ENTMaterial.h
      EPPGapMaterial.h
      ElasticBDMaterial.h
      ElasticMaterialThermal.h
      FRPConfinedConcrete.h
      FRPConfinedConcrete02.h
      FatigueMaterial.h
      #FedeasMaterial.h
      GNGMaterial.h
      #HardeningMaterial.h
      HardeningMaterial2.h
      HookGap.h
      HyperbolicGapMaterial.h
      HystereticMaterial.h
      HystereticPoly.h
      ImpactMaterial.h
      InitStrainMaterial.h
      InitStressMaterial.h
      KikuchiAikenHDR.h
      KikuchiAikenLRB.h
      Maxwell.h
      MinMaxMaterial.h
      ModIMKPeakOriented.h
      ModIMKPeakOriented02.h
      ModIMKPinching.h
      ModIMKPinching02.h
      MultiLinear.h
      Neoprene.h
      OOHystereticMaterial.h
      PathIndependentMaterial.h
      Pinching4Material.h
      PrestressedSteelMaterial.h
      RambergOsgoodSteel.h
      ReinforcingSteel.h
      ResilienceMaterialHR.h
      SAWSMaterial.h
      SPSW02.h
      SecantConcrete.h
      SelfCenteringMaterial.h
      SeriesMaterial.h
      ShearPanelMaterial.h
      SimpleFractureMaterial.h
      SLModel.h
      SmoothPSConcrete.h
      StainlessECThermal.h
      Steel01.h
      Steel01Thermal.h
      Steel02.h
      Steel02Fatigue.h
      Steel02Thermal.h
      Steel03.h
      Steel4.h
      SteelBRB.h
      SteelECThermal.h
      SteelMP.h
      TDConcrete.h
      TDConcreteEXP.h
      TDConcreteMC10.h
      TDConcreteMC10NL.h
      TensionOnlyMaterial.h
      UniaxialJ2Plasticity.h
      ViscousDamper.h
      ViscousMaterial.h
      WrapperUniaxialMaterial.h
      pyUCLA.h

      TriMatrix.h  # move to SRC/matrix ?
)


add_library(OPS_Material_f)

target_sources(OPS_Material_f PRIVATE
      DoddRestrepo.f
      STEELDR.f
      c14-SK-M.f
)

target_link_libraries(OPS_Material PUBLIC OPS_Material_f)
target_include_directories(OPS_Material PUBLIC ${CMAKE_CURRENT_LIST_DIR})

add_subdirectory(backbone)
add_subdirectory(stiffness)
add_subdirectory(strength)
add_subdirectory(unloading)
add_subdirectory(limitState)

add_subdirectory(PY)
add_subdirectory(snap)
add_subdirectory(fedeas)
add_subdirectory(drain)



