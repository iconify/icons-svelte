<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d25c1tbnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d25c1tbnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:shape-subtract-filled" {...props}></Icon>
