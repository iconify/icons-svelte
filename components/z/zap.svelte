<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxq-pglxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wxq-pglxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:zap" {...props}></Icon>
