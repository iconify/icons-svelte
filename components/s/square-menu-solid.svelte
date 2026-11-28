<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unhi2lbnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="unhi2lbnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:square-menu-solid" {...props}></Icon>
