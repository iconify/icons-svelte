<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9y-47bto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="q9y-47bto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:user-circle" {...props}></Icon>
