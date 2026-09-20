<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3bzaqblh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u3bzaqblh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:window-close" {...props}></Icon>
