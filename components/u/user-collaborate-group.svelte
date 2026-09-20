<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shvkgobsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="shvkgobsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:user-collaborate-group" {...props}></Icon>
