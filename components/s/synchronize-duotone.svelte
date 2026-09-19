<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/llper-sbd.css';
import '../../css/w/w8x1mclvl.css';
import '../../css/m/myfhbqbkv.css';
import '../../css/y/ykeey4ejx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="llper-sbd"/><path class="w8x1mclvl"/><path class="myfhbqbkv"/><path class="ykeey4ejx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:synchronize-duotone" {...props}></Icon>
