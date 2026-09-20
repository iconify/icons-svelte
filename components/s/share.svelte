<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nt60b7s8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nt60b7s8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:share" {...props}></Icon>
