<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bk1h49yzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bk1h49yzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:tree" {...props}></Icon>
