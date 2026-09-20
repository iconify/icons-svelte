<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cm0wiogcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cm0wiogcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:teslamate-dark" {...props}></Icon>
