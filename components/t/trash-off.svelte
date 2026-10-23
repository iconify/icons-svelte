<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnpeaacit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pnpeaacit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:trash-off" {...props}></Icon>
