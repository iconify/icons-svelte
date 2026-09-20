<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6yhfub-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d6yhfub-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:toilet" {...props}></Icon>
