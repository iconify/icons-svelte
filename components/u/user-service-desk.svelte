<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khutn8b6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="khutn8b6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:user-service-desk" {...props}></Icon>
