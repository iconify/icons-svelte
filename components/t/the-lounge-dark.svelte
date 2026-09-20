<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kklh9cc9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kklh9cc9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:the-lounge-dark" {...props}></Icon>
