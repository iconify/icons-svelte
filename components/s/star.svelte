<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wz9d9ozsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wz9d9ozsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:star" {...props}></Icon>
