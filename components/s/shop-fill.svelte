<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i36ln-bct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="i36ln-bct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:shop-fill" {...props}></Icon>
