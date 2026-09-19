<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9ow01geo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="g9ow01geo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:tangerine" {...props}></Icon>
