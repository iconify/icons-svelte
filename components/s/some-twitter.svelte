<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rf_p1xvlx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rf_p1xvlx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:some-twitter" {...props}></Icon>
