<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzo2gzbxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jzo2gzbxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:skates" {...props}></Icon>
