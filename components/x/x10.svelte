<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1exftzmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h1exftzmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:x10" {...props}></Icon>
