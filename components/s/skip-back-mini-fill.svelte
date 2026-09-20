<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzgijobcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jzgijobcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:skip-back-mini-fill" {...props}></Icon>
