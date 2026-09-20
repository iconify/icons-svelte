<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/b8sqeq3do.css';
import '../../css/g/gog0a1c5n.css';
import '../../css/c/cx25de5zj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="b8sqeq3do"/><path class="gog0a1c5n"/><circle class="cx25de5zj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:routing-line-duotone" {...props}></Icon>
