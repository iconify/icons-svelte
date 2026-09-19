<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tsthawb3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tsthawb3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:shopping-basket" {...props}></Icon>
