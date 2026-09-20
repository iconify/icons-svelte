<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3l7v_b6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n3l7v_b6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:stumbleupon-circle" {...props}></Icon>
