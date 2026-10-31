<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w05t1cbam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w05t1cbam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:voicemail-round" {...props}></Icon>
