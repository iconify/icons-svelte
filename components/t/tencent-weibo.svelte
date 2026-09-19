<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4b3u2b6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1216,"height":1792};
const content = `<path class="y4b3u2b6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:tencent-weibo" {...props}></Icon>
