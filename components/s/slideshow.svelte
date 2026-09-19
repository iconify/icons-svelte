<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufanw4bzm.css';
import '../../css/t/trfu-vbwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ufanw4bzm"/><path class="trfu-vbwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:slideshow" {...props}></Icon>
