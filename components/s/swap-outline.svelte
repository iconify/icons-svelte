<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9ujeac-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="q9ujeac-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:swap-outline" {...props}></Icon>
