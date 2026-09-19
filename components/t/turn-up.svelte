<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl3vdka2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yl3vdka2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:turn-up" {...props}></Icon>
