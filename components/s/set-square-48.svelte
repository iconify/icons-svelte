<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jz73jtbrx.css';
import '../../css/j/j8m18acze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jz73jtbrx"/><path class="j8m18acze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:set-square-48" {...props}></Icon>
