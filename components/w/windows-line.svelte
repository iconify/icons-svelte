<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mer4-ryno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mer4-ryno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:windows-line" {...props}></Icon>
