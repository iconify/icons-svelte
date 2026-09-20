<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtowsomii.css';
import '../../css/m/mq6hjubga.css';
import '../../css/i/i6zz6ccrg.css';
import '../../css/j/jztr7pbms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<g class="jtowsomii"><path class="mq6hjubga"/><path class="i6zz6ccrg"/><path class="jztr7pbms"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:swap" {...props}></Icon>
