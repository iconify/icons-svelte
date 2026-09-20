<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7gealbqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w7gealbqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:yunohost-light" {...props}></Icon>
