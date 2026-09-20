<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcq7ipbif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vcq7ipbif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:slackware" {...props}></Icon>
