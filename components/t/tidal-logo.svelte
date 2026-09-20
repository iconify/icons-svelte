<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6mgrzbqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y6mgrzbqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:tidal-logo" {...props}></Icon>
