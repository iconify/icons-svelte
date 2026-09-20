<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhprks6bk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uhprks6bk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:visio-meet-dark" {...props}></Icon>
