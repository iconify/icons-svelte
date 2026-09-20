<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dj2re3b1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dj2re3b1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:sewing-pin" {...props}></Icon>
