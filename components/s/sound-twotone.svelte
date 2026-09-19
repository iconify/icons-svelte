<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aij89zban.css';
import '../../css/q/qumb2w6hl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="aij89zban"/><path class="qumb2w6hl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:sound-twotone" {...props}></Icon>
