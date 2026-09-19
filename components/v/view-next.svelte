<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6tv-82-z.css';
import '../../css/u/uufe-4b8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i6tv-82-z"/><path class="uufe-4b8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:view-next" {...props}></Icon>
