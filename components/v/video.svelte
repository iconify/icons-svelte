<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t93rr5s2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t93rr5s2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:video" {...props}></Icon>
