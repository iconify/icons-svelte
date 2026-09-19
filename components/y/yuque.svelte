<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sf0-e1b2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="sf0-e1b2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:yuque" {...props}></Icon>
