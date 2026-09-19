<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z88dnnb8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="z88dnnb8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:up-circle-fill" {...props}></Icon>
