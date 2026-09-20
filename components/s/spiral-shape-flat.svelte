<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ied5ywnfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ied5ywnfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump-color:spiral-shape-flat" {...props}></Icon>
