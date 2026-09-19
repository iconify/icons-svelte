<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcvyz99kw.css';
import '../../css/x/x3cg0r7yx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wcvyz99kw"/><path class="x3cg0r7yx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:yin-yang" {...props}></Icon>
