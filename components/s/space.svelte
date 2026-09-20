<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_g3segb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v3_g3segb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:space" {...props}></Icon>
