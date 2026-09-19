<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hf1ii2b4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hf1ii2b4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:water-drop-alt-filled" {...props}></Icon>
