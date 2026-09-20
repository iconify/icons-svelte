<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xb7zws25x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xb7zws25x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:well-pump-powered" {...props}></Icon>
