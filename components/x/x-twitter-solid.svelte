<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u41y04bje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u41y04bje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:x-twitter-solid" {...props}></Icon>
