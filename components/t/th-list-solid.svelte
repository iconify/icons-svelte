<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anp_7vq1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="anp_7vq1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:th-list-solid" {...props}></Icon>
