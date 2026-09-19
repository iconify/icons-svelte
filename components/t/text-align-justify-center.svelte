<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/av5bkeb3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="av5bkeb3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:text-align-justify-center" {...props}></Icon>
