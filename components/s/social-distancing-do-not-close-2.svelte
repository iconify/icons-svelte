<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/c/cbprcirqx.css';
import '../../css/g/gian8go6d.css';
import '../../css/j/j5udpybsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cbprcirqx"/><path class="gian8go6d"/><path class="j5udpybsm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="covid:social-distancing-do-not-close-2" {...props}></Icon>
