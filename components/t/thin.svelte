<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfo1oe55t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jfo1oe55t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:thin" {...props}></Icon>
