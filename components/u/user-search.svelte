<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrz9yob5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yrz9yob5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:user-search" {...props}></Icon>
