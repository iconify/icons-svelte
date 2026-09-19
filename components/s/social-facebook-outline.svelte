<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lu5395ynk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lu5395ynk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:social-facebook-outline" {...props}></Icon>
