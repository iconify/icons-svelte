<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9lqrtbaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s9lqrtbaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:video-call" {...props}></Icon>
