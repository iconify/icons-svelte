<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rg8880iad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="rg8880iad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:unlock-fill" {...props}></Icon>
