<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/f/fcanezbfn.css';
import '../../css/s/sro91sbwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fcanezbfn"/><path class="sro91sbwr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:save-multiple" {...props}></Icon>
