<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/el3nms4in.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="el3nms4in"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:tag-alt" {...props}></Icon>
