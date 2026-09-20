<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r12dccgbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r12dccgbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:spectrum-fill" {...props}></Icon>
