<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/za715tbyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="za715tbyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:tencent-weibo" {...props}></Icon>
