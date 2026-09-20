<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pg40lro8p.css';
import '../../css/h/h6i0ijbtb.css';
import '../../css/m/msqsf4b6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="pg40lro8p"/><path clip-rule="evenodd" class="h6i0ijbtb"/><path class="msqsf4b6u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:star-badge-flat" {...props}></Icon>
