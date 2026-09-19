<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yq8ni5b_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="yq8ni5b_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:weibo-outline" {...props}></Icon>
