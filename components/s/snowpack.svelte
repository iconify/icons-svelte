<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clsdao61r.css';
import '../../css/l/l3ykglrhy.css';
import '../../css/c/c223jf_pj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="clsdao61r"><path class="l3ykglrhy"/><path class="c223jf_pj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:snowpack" {...props}></Icon>
