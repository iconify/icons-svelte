<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_46x3vmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x_46x3vmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:social-reddit" {...props}></Icon>
