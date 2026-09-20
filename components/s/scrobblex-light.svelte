<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cq8bs9b3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cq8bs9b3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:scrobblex-light" {...props}></Icon>
