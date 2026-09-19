<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jc_g6wb1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="jc_g6wb1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:signature-outlined" {...props}></Icon>
