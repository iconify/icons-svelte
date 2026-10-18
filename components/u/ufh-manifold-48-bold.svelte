<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rflk6vf2q.css';
import '../../css/o/ohc5ubgim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rflk6vf2q"/><path class="ohc5ubgim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ufh-manifold-48-bold" {...props}></Icon>
