<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qaiyq5bvp.css';
import '../../css/d/disvglb_n.css';
import '../../css/z/zcjdx8bee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="qaiyq5bvp"><path class="disvglb_n"/><path class="zcjdx8bee"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:svelte" {...props}></Icon>
