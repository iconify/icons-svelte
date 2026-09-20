<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kg1d0enhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kg1d0enhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:theme" {...props}></Icon>
