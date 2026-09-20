<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn38njbmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hn38njbmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:star-solid" {...props}></Icon>
