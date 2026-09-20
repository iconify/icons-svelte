<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7qqmifly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="r7qqmifly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:warehouse-1-solid" {...props}></Icon>
