<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g15t1bclt.css';
import '../../css/j/j0qwephmf.css';
import '../../css/q/qq-n_ibfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="g15t1bclt"/><path class="j0qwephmf"/><path class="qq-n_ibfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:water-treatment-48-bold" {...props}></Icon>
