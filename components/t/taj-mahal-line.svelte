<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vj7aiv6ea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vj7aiv6ea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:taj-mahal-line" {...props}></Icon>
