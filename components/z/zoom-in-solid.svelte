<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zs4p0ceyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="zs4p0ceyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:zoom-in-solid" {...props}></Icon>
