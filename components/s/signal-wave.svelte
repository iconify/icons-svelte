<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3f9i6byn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b3f9i6byn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:signal-wave" {...props}></Icon>
