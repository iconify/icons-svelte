<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/b/bnkim_jww.css';
import '../../css/w/wjg491cmr.css';
import '../../css/p/pl4wavb8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bnkim_jww"/><path class="wjg491cmr"/><path class="pl4wavb8s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:save" {...props}></Icon>
