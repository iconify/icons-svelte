<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vl_gb3b1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vl_gb3b1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:user-shield" {...props}></Icon>
