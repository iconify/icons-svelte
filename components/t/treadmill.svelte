<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/u/u40vykccn.css';
import '../../css/q/qtlvb393x.css';
import '../../css/v/v07nc-b0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u40vykccn"/><path class="qtlvb393x"/><path class="v07nc-b0h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:treadmill" {...props}></Icon>
