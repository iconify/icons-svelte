<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ep2_iimky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ep2_iimky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:telegram-outline" {...props}></Icon>
