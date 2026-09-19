<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pl9xnabwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pl9xnabwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:row" {...props}></Icon>
