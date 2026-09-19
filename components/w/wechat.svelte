<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cw5pvbc7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":1728};
const content = `<path class="cw5pvbc7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:wechat" {...props}></Icon>
