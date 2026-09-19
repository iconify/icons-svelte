<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tz2u_uuor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tz2u_uuor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:turn-l-1" {...props}></Icon>
