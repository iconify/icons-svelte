<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjpo16ghz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":24};
const content = `<path class="rjpo16ghz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:snowflake-8" {...props}></Icon>
