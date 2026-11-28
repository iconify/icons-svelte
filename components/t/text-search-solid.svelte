<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vy65659er.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vy65659er"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:text-search-solid" {...props}></Icon>
