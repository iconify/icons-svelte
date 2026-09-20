<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzjlihbdq.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/j/jomn23bik.css';
import '../../css/w/w0g0foxru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="lzjlihbdq"/><g class="jn8qy4bru"><path class="jomn23bik"/><path class="w0g0foxru"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:shamrock" {...props}></Icon>
