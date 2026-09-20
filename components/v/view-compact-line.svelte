<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zo3u2eb2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zo3u2eb2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:view-compact-line" {...props}></Icon>
