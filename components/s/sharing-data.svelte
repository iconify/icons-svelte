<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/a/avpgq1kjt.css';
import '../../css/b/bjlqahb4n.css';
import '../../css/t/tsy8wcblq.css';
import '../../css/a/aqt1dxftk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="avpgq1kjt"/><path class="bjlqahb4n"/><path class="tsy8wcblq"/><path class="aqt1dxftk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:sharing-data" {...props}></Icon>
