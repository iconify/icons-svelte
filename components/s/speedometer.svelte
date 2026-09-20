<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wosy2ac-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wosy2ac-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:speedometer" {...props}></Icon>
