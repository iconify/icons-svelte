<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0wzb5byf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d0wzb5byf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:select-all" {...props}></Icon>
