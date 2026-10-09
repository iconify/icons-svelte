<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/end2zdp7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="end2zdp7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:user-check-48" {...props}></Icon>
