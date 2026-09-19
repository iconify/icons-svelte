<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/a/ao10ozfpq.css';
import '../../css/c/c2bfh4dgq.css';
import '../../css/o/orzk3obqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="ao10ozfpq"/><path class="c2bfh4dgq"/><path class="orzk3obqe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:usb-memory-01" {...props}></Icon>
