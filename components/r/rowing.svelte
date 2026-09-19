<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ti4q6eknm.css';
import '../../css/i/iwk23h8tf.css';
import '../../css/j/jkcu7kbhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ti4q6eknm"><path class="iwk23h8tf"/><path class="jkcu7kbhq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:rowing" {...props}></Icon>
