<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdiyfl2-s.css';
import '../../css/d/d_sq5jfqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qdiyfl2-s"/><path class="d_sq5jfqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:save-solid" {...props}></Icon>
