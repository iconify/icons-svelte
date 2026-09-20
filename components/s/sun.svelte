<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtowsomii.css';
import '../../css/z/z3mr_0bdb.css';
import '../../css/y/y4ud7h78k.css';
import '../../css/g/ghnrqje-t.css';
import '../../css/h/ht860ybqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<g class="jtowsomii"><path class="z3mr_0bdb"/><g transform="translate(-210 -1)"><path class="y4ud7h78k"/><circle class="ghnrqje-t"/><path class="ht860ybqd"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:sun" {...props}></Icon>
