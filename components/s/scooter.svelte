<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ul832ibzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="ul832ibzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:scooter" {...props}></Icon>
