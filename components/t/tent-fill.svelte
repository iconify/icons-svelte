<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8-yimbcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i8-yimbcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:tent-fill" {...props}></Icon>
