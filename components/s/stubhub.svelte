<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x67-9lbyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x67-9lbyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:stubhub" {...props}></Icon>
