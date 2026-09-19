<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqmmymb5e.css';
import '../../css/f/fy2fydtce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hqmmymb5e"/><path class="fy2fydtce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:sync-sharp" {...props}></Icon>
