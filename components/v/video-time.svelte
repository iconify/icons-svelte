<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/k/kuc5c_btk.css';
import '../../css/j/jmdah2bcp.css';
import '../../css/v/v-ajdhbia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kuc5c_btk"/><path class="jmdah2bcp"/><path class="v-ajdhbia"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:video-time" {...props}></Icon>
