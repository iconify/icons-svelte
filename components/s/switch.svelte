<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtowsomii.css';
import '../../css/c/cue1yvi8n.css';
import '../../css/f/ftlh-bb6g.css';
import '../../css/g/gz7_nhb4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<g transform="translate(6 3)" class="jtowsomii"><path class="cue1yvi8n"/><circle class="ftlh-bb6g"/><path class="gz7_nhb4m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:switch" {...props}></Icon>
