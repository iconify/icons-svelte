<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ucu8i8bat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ucu8i8bat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:water-filled" {...props}></Icon>
