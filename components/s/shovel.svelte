<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2kvgvbvc.css';
import '../../css/f/fip4tbboc.css';
import '../../css/h/h_eof1loy.css';
import '../../css/t/tmtoxorob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="fip4tbboc"/><path class="h_eof1loy"/><path class="tmtoxorob"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:shovel" {...props}></Icon>
