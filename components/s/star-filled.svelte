<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhus0yb_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="nhus0yb_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:star-filled" {...props}></Icon>
