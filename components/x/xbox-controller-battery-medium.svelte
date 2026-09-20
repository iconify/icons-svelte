<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fslvuzacs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fslvuzacs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:xbox-controller-battery-medium" {...props}></Icon>
