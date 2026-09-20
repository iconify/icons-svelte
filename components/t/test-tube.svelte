<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/uxreuzyhb.css';
import '../../css/x/xpt3qjbnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="ft5dv1b6b"><path class="uxreuzyhb"/><path class="xpt3qjbnh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:test-tube" {...props}></Icon>
