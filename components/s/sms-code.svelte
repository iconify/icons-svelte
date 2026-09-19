<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/m/m-7u57b3n.css';
import '../../css/d/d3i_dbbrj.css';
import '../../css/e/ep70jebpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m-7u57b3n"/><path class="d3i_dbbrj"/><path class="ep70jebpf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:sms-code" {...props}></Icon>
