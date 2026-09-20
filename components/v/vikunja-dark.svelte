<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axej3o6of.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="axej3o6of"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:vikunja-dark" {...props}></Icon>
