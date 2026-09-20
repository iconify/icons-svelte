<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3ox78bwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q3ox78bwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:torah" {...props}></Icon>
