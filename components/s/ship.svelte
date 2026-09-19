<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcq5-ib4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="kcq5-ib4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:ship" {...props}></Icon>
