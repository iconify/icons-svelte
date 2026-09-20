<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mw-wv0b3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="mw-wv0b3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:table" {...props}></Icon>
