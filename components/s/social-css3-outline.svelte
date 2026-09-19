<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixdm9acjc.css';
import '../../css/i/irl9z8uwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ixdm9acjc"/><path class="irl9z8uwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:social-css3-outline" {...props}></Icon>
