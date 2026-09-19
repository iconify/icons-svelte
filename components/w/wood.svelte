<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/p8nulxl3s.css';
import '../../css/p/pap5xhb-b.css';
import '../../css/v/vgionz7jo.css';
import '../../css/f/f51xn97ff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="p8nulxl3s"/><path class="pap5xhb-b"/><path class="vgionz7jo"/><path class="f51xn97ff"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:wood" {...props}></Icon>
