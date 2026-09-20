<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/v/vwasf1fzc.css';
import '../../css/e/elti8xbhv.css';
import '../../css/x/xizglbc3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><circle class="vwasf1fzc"/><circle class="elti8xbhv"/><path class="xizglbc3d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:tablets" {...props}></Icon>
