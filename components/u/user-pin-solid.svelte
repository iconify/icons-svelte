<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tng3gzelg.css';
import '../../css/h/hzpmfc_wi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tng3gzelg"/><path class="hzpmfc_wi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:user-pin-solid" {...props}></Icon>
