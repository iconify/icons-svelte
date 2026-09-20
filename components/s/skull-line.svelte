<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5ogn4brv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q5ogn4brv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:skull-line" {...props}></Icon>
