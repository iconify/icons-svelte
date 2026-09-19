<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0gllcbmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="a0gllcbmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:two" {...props}></Icon>
