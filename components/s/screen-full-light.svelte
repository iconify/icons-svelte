<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swx55lw8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="swx55lw8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:screen-full-light" {...props}></Icon>
