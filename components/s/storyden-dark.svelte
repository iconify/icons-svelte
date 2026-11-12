<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmibnzbxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nmibnzbxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:storyden-dark" {...props}></Icon>
