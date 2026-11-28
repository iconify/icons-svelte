<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fp0fjgbrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fp0fjgbrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:venus-solid" {...props}></Icon>
