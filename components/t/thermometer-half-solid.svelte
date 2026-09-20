<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jw6_6gx7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jw6_6gx7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:thermometer-half-solid" {...props}></Icon>
