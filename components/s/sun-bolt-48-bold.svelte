<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1iqz1-zd.css';
import '../../css/r/r0d7qbcdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h1iqz1-zd"/><path class="r0d7qbcdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sun-bolt-48-bold" {...props}></Icon>
