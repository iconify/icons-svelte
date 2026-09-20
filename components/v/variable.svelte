<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h38ps2bdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h38ps2bdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:variable" {...props}></Icon>
