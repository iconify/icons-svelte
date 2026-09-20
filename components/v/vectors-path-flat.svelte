<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/q/qf_kb0bbs.css';
import '../../css/a/a4gmabcpu.css';
import '../../css/m/mzxbdgbpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="qf_kb0bbs"/><path class="a4gmabcpu"/><path class="mzxbdgbpf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:vectors-path-flat" {...props}></Icon>
