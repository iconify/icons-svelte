<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jork_dbtm.css';
import '../../css/w/wsj8ofa5i.css';
import '../../css/w/w-kmabubr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jork_dbtm"/><path class="wsj8ofa5i"/><path class="w-kmabubr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:technology-device-wearable-smart-watch-circle-app-2-bold" {...props}></Icon>
