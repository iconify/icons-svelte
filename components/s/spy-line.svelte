<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tue2n2r4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tue2n2r4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:spy-line" {...props}></Icon>
