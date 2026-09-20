<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anv3f7brl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="anv3f7brl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:univention-corporate-server-light" {...props}></Icon>
