<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-4wlnb7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1600};
const content = `<path class="z-4wlnb7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:sms" {...props}></Icon>
