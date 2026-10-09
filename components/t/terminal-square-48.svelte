<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3q6uacna.css';
import '../../css/v/vuoldp53f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="v3q6uacna"/><path class="vuoldp53f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:terminal-square-48" {...props}></Icon>
