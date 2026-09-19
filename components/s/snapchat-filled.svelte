<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqtsj--xx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="kqtsj--xx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:snapchat-filled" {...props}></Icon>
