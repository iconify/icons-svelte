<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_08yzbiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":504};
const content = `<path class="z_08yzbiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:tag" {...props}></Icon>
