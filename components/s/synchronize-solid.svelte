<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anom_cxjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="anom_cxjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:synchronize-solid" {...props}></Icon>
