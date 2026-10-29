<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2kvgvbvc.css';
import '../../css/d/dmvc1yldm.css';
import '../../css/f/fx38fwtmt.css';
import '../../css/g/gdom9jbqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="dmvc1yldm wm-k"/><path class="fx38fwtmt wm-s"/><path class="gdom9jbqk wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:user-clock" {...props}></Icon>
