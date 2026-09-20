<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uieezdbmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uieezdbmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:vert-dark" {...props}></Icon>
