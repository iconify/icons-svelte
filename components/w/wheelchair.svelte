<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/c_semibtt.css';
import '../../css/g/g_82qn13v.css';
import '../../css/m/mc4nh2bkz.css';
import '../../css/e/esan_6mzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="ft5dv1b6b"><path class="c_semibtt"/><path class="g_82qn13v"/><path class="mc4nh2bkz"/><path class="esan_6mzl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:wheelchair" {...props}></Icon>
