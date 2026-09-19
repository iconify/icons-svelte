<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fncz_m7by.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":24};
const content = `<path class="fncz_m7by"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:snowflake" {...props}></Icon>
