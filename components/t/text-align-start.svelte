<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4zl2bc_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h4zl2bc_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="doodle-icons:text-align-start" {...props}></Icon>
