<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vug-92bye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vug-92bye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:wrench-circle-solid" {...props}></Icon>
