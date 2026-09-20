<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5a3ny35e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="d5a3ny35e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:waving-hand-solid" {...props}></Icon>
