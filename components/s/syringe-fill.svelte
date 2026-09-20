<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i__1--b9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i__1--b9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:syringe-fill" {...props}></Icon>
