<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6si3pb8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y6si3pb8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:swipe-up-filled" {...props}></Icon>
