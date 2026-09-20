<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kww23jbbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kww23jbbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:teratail" {...props}></Icon>
