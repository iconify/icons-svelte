<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i85qzcn-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i85qzcn-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shield-off-48" {...props}></Icon>
