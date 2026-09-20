<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kf-ki8wwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kf-ki8wwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:volume-off-solid" {...props}></Icon>
