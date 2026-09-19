<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2h-50wuc.css';
import '../../css/i/imgt2lbqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="d2h-50wuc"/><path class="imgt2lbqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:shop-twotone" {...props}></Icon>
