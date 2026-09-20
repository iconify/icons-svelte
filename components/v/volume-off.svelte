<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgr529r6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="qgr529r6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:volume-off" {...props}></Icon>
