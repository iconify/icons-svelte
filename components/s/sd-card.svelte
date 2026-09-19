<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6v6ah50v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="r6v6ah50v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:sd-card" {...props}></Icon>
