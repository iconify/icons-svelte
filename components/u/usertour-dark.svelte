<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltn65fiok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ltn65fiok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:usertour-dark" {...props}></Icon>
