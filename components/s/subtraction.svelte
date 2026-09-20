<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwl48ebgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uwl48ebgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:subtraction" {...props}></Icon>
