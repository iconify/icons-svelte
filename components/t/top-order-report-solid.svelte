<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvznjjpny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="jvznjjpny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:top-order-report-solid" {...props}></Icon>
