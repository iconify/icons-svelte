<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zr_v2zbad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zr_v2zbad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:snowflake" {...props}></Icon>
