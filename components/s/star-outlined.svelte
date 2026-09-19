<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmiaxyeht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="zmiaxyeht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:star-outlined" {...props}></Icon>
