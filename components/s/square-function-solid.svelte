<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgu9w_bap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zgu9w_bap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:square-function-solid" {...props}></Icon>
