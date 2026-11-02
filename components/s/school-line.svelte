<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3goaoidn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e3goaoidn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:school-line" {...props}></Icon>
