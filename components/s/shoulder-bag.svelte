<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/m/mmnjdfbni.css';
import '../../css/f/f2r7aqcds.css';
import '../../css/t/tt4z5sb8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path class="mmnjdfbni"/><path class="f2r7aqcds"/><circle class="tt4z5sb8s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:shoulder-bag" {...props}></Icon>
