<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/n/n3_pvkb9w.css';
import '../../css/c/c2w87rbfl.css';
import '../../css/r/r4ow6xb6m.css';
import '../../css/v/v7qa0nzlx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="n3_pvkb9w"/><path class="c2w87rbfl"/><path class="r4ow6xb6m"/><path class="v7qa0nzlx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:task-list-clipboard-check" {...props}></Icon>
