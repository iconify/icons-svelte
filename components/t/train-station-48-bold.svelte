<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2ev-6zgp.css';
import '../../css/c/cpgk2abrw.css';
import '../../css/i/ikk4chbfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="b2ev-6zgp"/><path class="cpgk2abrw"/><path class="ikk4chbfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:train-station-48-bold" {...props}></Icon>
