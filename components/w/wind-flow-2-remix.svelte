<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o26vtib_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="o26vtib_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:wind-flow-2-remix" {...props}></Icon>
