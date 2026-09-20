<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtowsomii.css';
import '../../css/o/om1jfjbon.css';
import '../../css/h/hghunxbuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<g transform="translate(3 6)" class="jtowsomii"><path class="om1jfjbon"/><circle class="hghunxbuh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:wifi" {...props}></Icon>
