<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvfkai1wh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tvfkai1wh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:voicemail-solid" {...props}></Icon>
