<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae_qjzbwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ae_qjzbwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:screenshot-line" {...props}></Icon>
