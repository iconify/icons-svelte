<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5rmaob2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":288,"height":512};
const content = `<path class="k5rmaob2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:wine-glass-alt" {...props}></Icon>
