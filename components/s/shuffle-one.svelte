<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3lph30dl.css';
import '../../css/w/wkk1f-b-h.css';
import '../../css/g/ge1mxvm8x.css';
import '../../css/h/hsmz4cbpa.css';
import '../../css/j/j5wf84hfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="l3lph30dl"><path class="wkk1f-b-h"/><path class="ge1mxvm8x"/><path class="hsmz4cbpa"/><path class="j5wf84hfz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:shuffle-one" {...props}></Icon>
