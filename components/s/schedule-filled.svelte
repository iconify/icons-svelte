<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zo9ugs2zi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="zo9ugs2zi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:schedule-filled" {...props}></Icon>
