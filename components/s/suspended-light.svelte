<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iso_4ebmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iso_4ebmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:suspended-light" {...props}></Icon>
