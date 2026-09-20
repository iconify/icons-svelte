<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hc2ypxcmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hc2ypxcmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:vis-gauge" {...props}></Icon>
