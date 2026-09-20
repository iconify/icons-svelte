<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/x/xed0uxxmk.css';
import '../../css/e/eaof3obga.css';
import '../../css/y/yu-tszbdn.css';
import '../../css/v/vbpr_wbom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="xed0uxxmk"/><path class="eaof3obga"/><path class="yu-tszbdn"/><path class="vbpr_wbom"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:widget-2-outline" {...props}></Icon>
