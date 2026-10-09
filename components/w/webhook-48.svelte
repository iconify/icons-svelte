<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejvdg2q1j.css';
import '../../css/p/p2_kkklpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ejvdg2q1j"/><path class="p2_kkklpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:webhook-48" {...props}></Icon>
