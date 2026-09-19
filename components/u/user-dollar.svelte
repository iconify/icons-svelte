<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/w/wqr-41aca.css';
import '../../css/m/misun9bmf.css';
import '../../css/j/jterakbqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wqr-41aca"/><circle class="misun9bmf"/><path class="jterakbqr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:user-dollar" {...props}></Icon>
