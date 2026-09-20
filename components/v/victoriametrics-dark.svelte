<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_1jafb3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d_1jafb3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:victoriametrics-dark" {...props}></Icon>
