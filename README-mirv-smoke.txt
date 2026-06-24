HLAE Source2 hook build with mirv_smoke support.

Commands:
  mirv_smoke volumeAlpha <0..1>
  mirv_smoke overlay <0|1>

Suggested test:
  mirv_smoke volumeAlpha 0.35
  mirv_smoke overlay 0

Restore defaults:
  mirv_smoke volumeAlpha 1
  mirv_smoke overlay 1

Built from local AdvancedFX checkout with RenderSystemDX11Hooks.cpp smoke patch.
Use only for demo/recording workflows launched insecure through HLAE.