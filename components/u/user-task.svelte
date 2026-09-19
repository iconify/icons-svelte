<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/looy1fptd.css';
import '../../css/b/bstbjibrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2000,"height":2000};
const content = `<g transform="translate(0 947.638)"><rect class="looy1fptd"/><path class="bstbjibrz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:user-task" {...props}></Icon>
