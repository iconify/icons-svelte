<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-8f62uxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d-8f62uxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:test-tube-solid" {...props}></Icon>
