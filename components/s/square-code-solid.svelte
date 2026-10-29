<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4w_rw5oq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u4w_rw5oq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:square-code-solid" {...props}></Icon>
