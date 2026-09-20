<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/y/y-honm_li.css';
import '../../css/d/dq1ulvyil.css';
import '../../css/o/o8w0orrwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y-honm_li"/><path class="dq1ulvyil"/><path class="o8w0orrwc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:science-molecule" {...props}></Icon>
