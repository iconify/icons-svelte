<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/b/bgk_arrkt.css';
import '../../css/f/fdtkzu5vr.css';
import '../../css/c/cf56gjb1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bgk_arrkt"/><path class="fdtkzu5vr"/><path class="cf56gjb1f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:upload-03" {...props}></Icon>
