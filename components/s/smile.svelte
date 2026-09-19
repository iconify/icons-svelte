<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6q-f6bnh.css';
import '../../css/n/ny4ycobxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r6q-f6bnh"/><path class="ny4ycobxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:smile" {...props}></Icon>
