<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsai2gy0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="zsai2gy0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:shopping-basket-2" {...props}></Icon>
