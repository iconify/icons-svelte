<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qm1fwac7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qm1fwac7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:testin" {...props}></Icon>
