<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldhof1blp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ldhof1blp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:text-outline" {...props}></Icon>
