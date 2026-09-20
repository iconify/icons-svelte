<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjl893inq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rjl893inq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:simplex" {...props}></Icon>
