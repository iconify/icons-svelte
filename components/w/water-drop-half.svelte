<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lq9_pobzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lq9_pobzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:water-drop-half" {...props}></Icon>
