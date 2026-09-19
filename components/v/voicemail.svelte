<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6-h_fbma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h6-h_fbma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:voicemail" {...props}></Icon>
