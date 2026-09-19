<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oi2vwibfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="oi2vwibfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:skype-filled" {...props}></Icon>
