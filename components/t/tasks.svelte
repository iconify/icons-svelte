<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/r/r-kinobif.css';
import '../../css/q/qrnzx23eu.css';
import '../../css/l/ltp3o44gf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r-kinobif"/><path class="qrnzx23eu"/><path class="ltp3o44gf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:tasks" {...props}></Icon>
