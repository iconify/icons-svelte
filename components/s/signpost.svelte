<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jca3u64_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jca3u64_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:signpost" {...props}></Icon>
