<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkje3ybpz.css';
import '../../css/d/d34fk4x7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gkje3ybpz"/><path class="d34fk4x7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:zoom-out-48" {...props}></Icon>
