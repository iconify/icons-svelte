<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to3w6o15e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="to3w6o15e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:user-minus" {...props}></Icon>
