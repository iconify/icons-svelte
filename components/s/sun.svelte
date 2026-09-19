<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0z8wjhfw.css';
import '../../css/a/alnfi4bhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m0z8wjhfw"/><path class="alnfi4bhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:sun" {...props}></Icon>
