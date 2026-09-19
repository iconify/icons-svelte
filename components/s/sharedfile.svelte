<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tj-m0unih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1025};
const content = `<path class="tj-m0unih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:sharedfile" {...props}></Icon>
