<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0sq_bx6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b0sq_bx6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:text-align-left-01" {...props}></Icon>
