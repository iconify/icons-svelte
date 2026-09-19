<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhc54hbav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bhc54hbav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:tag" {...props}></Icon>
