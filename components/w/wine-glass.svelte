<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yr_4ze5bh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":288,"height":512};
const content = `<path class="yr_4ze5bh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:wine-glass" {...props}></Icon>
