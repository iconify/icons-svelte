<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vi36ombor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vi36ombor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:shape-outline-filled" {...props}></Icon>
