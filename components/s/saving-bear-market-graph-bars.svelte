<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/f/f-i5wnbdl.css';
import '../../css/d/djk6jvnak.css';
import '../../css/m/m5vvnhx0o.css';
import '../../css/g/g6a-1bcjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="f-i5wnbdl"/><path class="djk6jvnak"/><path class="m5vvnhx0o"/><path class="g6a-1bcjo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:saving-bear-market-graph-bars" {...props}></Icon>
