<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unqzfdcpy.css';
import '../../css/p/pqf5v6bke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="unqzfdcpy"/><path class="pqf5v6bke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sort-asc-48" {...props}></Icon>
