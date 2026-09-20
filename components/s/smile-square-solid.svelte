<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfdry5kvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sfdry5kvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:smile-square-solid" {...props}></Icon>
