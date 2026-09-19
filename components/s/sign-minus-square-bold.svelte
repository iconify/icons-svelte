<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2a9-fy8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j2a9-fy8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sign-minus-square-bold" {...props}></Icon>
