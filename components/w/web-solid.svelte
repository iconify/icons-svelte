<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yctc6jbnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yctc6jbnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:web-solid" {...props}></Icon>
