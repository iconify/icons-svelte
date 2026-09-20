<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyazfqf8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lyazfqf8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:twitter-dark" {...props}></Icon>
