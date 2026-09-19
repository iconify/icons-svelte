<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4_q5fqio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x4_q5fqio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:user-plus" {...props}></Icon>
