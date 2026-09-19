<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axj77dh9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="axj77dh9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:sketch-circle" {...props}></Icon>
