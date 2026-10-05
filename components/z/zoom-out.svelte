<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/a/abwis6bpt.css';
import '../../css/f/fop159nlm.css';
import '../../css/m/mofdx0msy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="abwis6bpt"/><path class="fop159nlm"/><path class="mofdx0msy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:zoom-out" {...props}></Icon>
