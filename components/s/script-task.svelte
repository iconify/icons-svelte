<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds6outb7u.css';
import '../../css/r/rhman1omc.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nyqd9cc_q.css';
import '../../css/g/gzspqv64m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2000,"height":2000};
const content = `<g transform="translate(0 947.638)" class="ds6outb7u"><rect class="rhman1omc"/><g class="cuyn6tgcc"><path class="nyqd9cc_q"/><path class="gzspqv64m"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:script-task" {...props}></Icon>
