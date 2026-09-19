<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9rz2pk3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m9rz2pk3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:triangle-round-rectangle" {...props}></Icon>
