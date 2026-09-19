<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/i/ief88gblg.css';
import '../../css/d/d1xlaxbzx.css';
import '../../css/l/l00awn5kw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ief88gblg"/><path class="d1xlaxbzx"/><path class="l00awn5kw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:square-user-round" {...props}></Icon>
