<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/de9ov5bov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="de9ov5bov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:stock-solid" {...props}></Icon>
