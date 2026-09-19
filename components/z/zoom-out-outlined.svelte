<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f205myb-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="f205myb-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:zoom-out-outlined" {...props}></Icon>
