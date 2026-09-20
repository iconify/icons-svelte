<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kg9lgabvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kg9lgabvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:spinner-solid" {...props}></Icon>
