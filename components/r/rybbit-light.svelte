<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/or3w7ac_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="or3w7ac_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rybbit-light" {...props}></Icon>
