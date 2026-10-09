<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fyl30e_uw.css';
import '../../css/v/vg4zk5bim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fyl30e_uw"/><path class="vg4zk5bim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:share-48" {...props}></Icon>
