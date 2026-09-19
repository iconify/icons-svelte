<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmnb7-83l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="zmnb7-83l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:shrink-outline" {...props}></Icon>
