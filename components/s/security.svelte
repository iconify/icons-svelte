<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/l/l4ahjrb2f.css';
import '../../css/c/cb333fqxl.css';
import '../../css/i/i1daf0olr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l4ahjrb2f"/><path class="cb333fqxl"/><path class="i1daf0olr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:security" {...props}></Icon>
