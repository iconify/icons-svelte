<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1kuotbsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f1kuotbsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tautulli-light" {...props}></Icon>
