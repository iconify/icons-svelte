<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pj2nowpcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="pj2nowpcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:trophy-outline" {...props}></Icon>
