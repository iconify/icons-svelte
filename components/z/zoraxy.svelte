<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3p79uh_k.css';
import '../../css/h/h68tk6bxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b3p79uh_k"/><path class="h68tk6bxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:zoraxy" {...props}></Icon>
