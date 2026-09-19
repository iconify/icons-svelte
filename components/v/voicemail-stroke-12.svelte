<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/h/h2po03bxv.css';
import '../../css/f/f1er5e3yx.css';
import '../../css/d/dw0vfobux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<g class="h01tyzbfu"><circle class="h2po03bxv"/><circle class="f1er5e3yx"/><path class="dw0vfobux"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:voicemail-stroke-12" {...props}></Icon>
