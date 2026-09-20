<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_k3o6i9g.css';
import '../../css/v/vpv8vrdpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u_k3o6i9g"/><path class="vpv8vrdpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:voidauth-light" {...props}></Icon>
