<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofvi3bb5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ofvi3bb5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="doodle-icons:underline" {...props}></Icon>
