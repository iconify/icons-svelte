<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-aa569ok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="m-aa569ok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:x-outlined" {...props}></Icon>
