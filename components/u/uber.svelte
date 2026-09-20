<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z190gry6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z190gry6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:uber" {...props}></Icon>
