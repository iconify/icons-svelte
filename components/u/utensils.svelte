<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kokupk2te.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":416,"height":512};
const content = `<path class="kokupk2te"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:utensils" {...props}></Icon>
