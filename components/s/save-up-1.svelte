<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8xvvwglv.css';
import '../../css/p/p__g4pb1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f8xvvwglv"/><path class="p__g4pb1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:save-up-1" {...props}></Icon>
