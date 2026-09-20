<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knxpz_b9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="knxpz_b9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:snowflake" {...props}></Icon>
