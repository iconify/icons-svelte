<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvya9l6dj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mvya9l6dj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:sort-one" {...props}></Icon>
