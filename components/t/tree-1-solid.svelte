<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csypp5bmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="csypp5bmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:tree-1-solid" {...props}></Icon>
