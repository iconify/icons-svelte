<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcp-osn-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bcp-osn-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:vector-spline" {...props}></Icon>
