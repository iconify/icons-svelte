<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyl66ccho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nyl66ccho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:tencent-weibo" {...props}></Icon>
