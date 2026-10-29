<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjtauk8ix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zjtauk8ix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:tag-x" {...props}></Icon>
