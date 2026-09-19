<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ump_5_t_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ump_5_t_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:windows" {...props}></Icon>
