<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3u49vbln.css';
import '../../css/s/sarekibri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w3u49vbln"/><path class="sarekibri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:satellite-alt" {...props}></Icon>
