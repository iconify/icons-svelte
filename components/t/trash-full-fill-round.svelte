<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m81vs0cnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m81vs0cnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:trash-full-fill-round" {...props}></Icon>
