<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dl5jfab4x.css';
import '../../css/l/luhh6r95d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dl5jfab4x"/><path class="luhh6r95d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:waste-manhole" {...props}></Icon>
