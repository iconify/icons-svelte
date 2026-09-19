<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhfv55b2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yhfv55b2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:social-vimeo-outline" {...props}></Icon>
