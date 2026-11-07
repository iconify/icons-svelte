<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u--1m-bou.css';
import '../../css/v/vidg63bsd.css';
import '../../css/p/pocrugbev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u--1m-bou"/><path class="vidg63bsd"/><path class="pocrugbev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:three-squares-bold" {...props}></Icon>
