<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6lu45vzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e6lu45vzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:signal-light" {...props}></Icon>
