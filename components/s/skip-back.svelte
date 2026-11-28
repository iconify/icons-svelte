<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jta8ipbkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jta8ipbkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:skip-back" {...props}></Icon>
