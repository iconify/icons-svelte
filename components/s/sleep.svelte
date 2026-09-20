<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfgbu1m_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wfgbu1m_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:sleep" {...props}></Icon>
