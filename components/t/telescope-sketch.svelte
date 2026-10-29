<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/qcj0w7beu.css';
import '../../css/g/go8wiqrnw.css';
import '../../css/j/jj7v60bhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="qcj0w7beu wm-a"/><path class="go8wiqrnw wm-k"/><path class="jj7v60bhl wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:telescope-sketch" {...props}></Icon>
