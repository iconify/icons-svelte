<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fuun46b6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="fuun46b6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:running-water-alt-outline" {...props}></Icon>
