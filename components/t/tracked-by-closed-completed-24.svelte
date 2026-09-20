<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilw1vqb3q.css';
import '../../css/m/mtfwbcc5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ilw1vqb3q"/><path class="mtfwbcc5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:tracked-by-closed-completed-24" {...props}></Icon>
