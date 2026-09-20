<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/veeq4sbph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="veeq4sbph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:view-dashboard" {...props}></Icon>
