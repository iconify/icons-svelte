<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8kyhtbde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="e8kyhtbde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:square-small" {...props}></Icon>
