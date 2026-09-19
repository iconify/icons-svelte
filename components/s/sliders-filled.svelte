<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pi4rw9ffy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="pi4rw9ffy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:sliders-filled" {...props}></Icon>
