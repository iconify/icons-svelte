<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1sol0n2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="w1sol0n2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:threads-filled" {...props}></Icon>
