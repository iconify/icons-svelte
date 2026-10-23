<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tw9-occkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tw9-occkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:video-off" {...props}></Icon>
