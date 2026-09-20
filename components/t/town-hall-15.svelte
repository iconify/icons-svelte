<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7c0j03cm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="l7c0j03cm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:town-hall-15" {...props}></Icon>
