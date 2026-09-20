<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvad91upb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bvad91upb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:time-line" {...props}></Icon>
