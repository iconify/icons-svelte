<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/khy8p4b-y.css';
import '../../css/g/gmzwbacmo.css';
import '../../css/v/v7peg9b3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="khy8p4b-y"/><path class="gmzwbacmo wm-k"/><path class="v7peg9b3t wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:settings-sketch" {...props}></Icon>
