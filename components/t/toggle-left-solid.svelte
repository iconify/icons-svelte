<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awv-u-rtm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="awv-u-rtm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:toggle-left-solid" {...props}></Icon>
