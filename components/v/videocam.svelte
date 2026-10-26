<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlmx0q-5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rlmx0q-5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="doodle-icons:videocam" {...props}></Icon>
