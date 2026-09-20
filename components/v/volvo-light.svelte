<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fde7o7i7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fde7o7i7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:volvo-light" {...props}></Icon>
