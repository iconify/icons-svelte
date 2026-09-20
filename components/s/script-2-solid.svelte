<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atsev825d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="atsev825d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:script-2-solid" {...props}></Icon>
