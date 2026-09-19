<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yv0885bbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yv0885bbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:snowflake" {...props}></Icon>
