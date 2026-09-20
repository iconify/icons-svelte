<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmofqyjxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xmofqyjxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:vis-bar-horizontal-stacked" {...props}></Icon>
