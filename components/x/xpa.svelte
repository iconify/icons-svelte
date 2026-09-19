<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8u07bc3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m8u07bc3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:xpa" {...props}></Icon>
