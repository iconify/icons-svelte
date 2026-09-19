<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2vg_9bjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o2vg_9bjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:user-circle-filled" {...props}></Icon>
