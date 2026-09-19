<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/l/ldmkd1blz.css';
import '../../css/x/xw25w-bst.css';
import '../../css/r/rie-5-99g.css';
import '../../css/k/k3djch2so.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ldmkd1blz"/><path class="xw25w-bst"/><path class="rie-5-99g"/><path class="k3djch2so"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="covid:vaccine-protection-face-shield-1" {...props}></Icon>
