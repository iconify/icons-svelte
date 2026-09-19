<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_2lkqbxb.css';
import '../../css/u/u8rgrcqdt.css';
import '../../css/x/x1h184bjr.css';
import '../../css/s/seqarwbcd.css';
import '../../css/f/ffvfie7iu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="t_2lkqbxb"><path class="u8rgrcqdt"/><path class="x1h184bjr"/><path class="seqarwbcd"/><path class="ffvfie7iu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:tauri" {...props}></Icon>
