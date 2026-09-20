<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exill43ak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="exill43ak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:signal-full" {...props}></Icon>
