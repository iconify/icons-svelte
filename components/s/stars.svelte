<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp29vub2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bp29vub2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:stars" {...props}></Icon>
