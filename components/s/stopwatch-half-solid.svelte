<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxm9n-bwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="cxm9n-bwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:stopwatch-half-solid" {...props}></Icon>
