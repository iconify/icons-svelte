<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tg-4g4b3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tg-4g4b3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:work-order-abnormal-outline" {...props}></Icon>
