<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/f/f_362pbxn.css';
import '../../css/p/pqb0a8b9a.css';
import '../../css/z/zr7knrf6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle class="f_362pbxn"/><path class="pqb0a8b9a"/><path class="zr7knrf6z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:watch-01" {...props}></Icon>
