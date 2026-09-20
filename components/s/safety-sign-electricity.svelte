<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zu4c-gk5y.css';
import '../../css/b/b76l5ee_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zu4c-gk5y"/><path class="b76l5ee_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:safety-sign-electricity" {...props}></Icon>
