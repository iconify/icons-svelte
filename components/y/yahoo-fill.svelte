<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfzb2rv_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="qfzb2rv_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:yahoo-fill" {...props}></Icon>
