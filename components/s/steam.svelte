<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atxd3d4li.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="atxd3d4li"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:steam" {...props}></Icon>
