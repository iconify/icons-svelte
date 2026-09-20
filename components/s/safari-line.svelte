<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xneq1mbiq.css';
import '../../css/o/okweau1mj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xneq1mbiq"/><path class="okweau1mj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:safari-line" {...props}></Icon>
