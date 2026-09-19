<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_9_k6c_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="h_9_k6c_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:underline-outlined" {...props}></Icon>
