<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jk3br8gfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jk3br8gfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:unraid-dark" {...props}></Icon>
