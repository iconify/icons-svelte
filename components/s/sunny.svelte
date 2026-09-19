<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv90u3bto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="nv90u3bto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:sunny" {...props}></Icon>
