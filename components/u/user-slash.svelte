<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aj5k6uu3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="aj5k6uu3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:user-slash" {...props}></Icon>
