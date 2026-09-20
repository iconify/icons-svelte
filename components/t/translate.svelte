<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zeuusybaq.css';
import '../../css/d/d38qlsbag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zeuusybaq"/><path class="d38qlsbag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:translate" {...props}></Icon>
