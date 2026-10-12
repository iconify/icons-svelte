<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5nd0vb2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s5nd0vb2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rows-48-bold" {...props}></Icon>
