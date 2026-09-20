<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tauy7pbyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tauy7pbyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:ruler-solid" {...props}></Icon>
