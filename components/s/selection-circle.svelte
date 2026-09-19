<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz9z_2a2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nz9z_2a2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:selection-circle" {...props}></Icon>
