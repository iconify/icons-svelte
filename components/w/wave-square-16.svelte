<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ms14et43n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ms14et43n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:wave-square-16" {...props}></Icon>
