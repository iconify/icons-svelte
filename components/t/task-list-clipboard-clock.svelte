<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/x/xkabgyb9j.css';
import '../../css/u/urosuxb4j.css';
import '../../css/x/xc3sa6bii.css';
import '../../css/k/k_iln5sfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="xkabgyb9j"/><path class="urosuxb4j"/><path class="xc3sa6bii"/><path class="k_iln5sfj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:task-list-clipboard-clock" {...props}></Icon>
