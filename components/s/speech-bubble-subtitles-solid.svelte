<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdm8trd6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bdm8trd6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:speech-bubble-subtitles-solid" {...props}></Icon>
