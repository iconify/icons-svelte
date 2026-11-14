<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/y/y6yyhbwot.css';
import '../../css/g/gdkakebdu.css';
import '../../css/o/o9qs78bqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="y6yyhbwot"/><path class="gdkakebdu"/><path class="o9qs78bqo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="evicons:route-to-charger" {...props}></Icon>
