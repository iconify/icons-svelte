<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9jb7kaqf.css';
import '../../css/j/jimnbhblw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m9jb7kaqf"/><path class="jimnbhblw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:switchgear-48" {...props}></Icon>
