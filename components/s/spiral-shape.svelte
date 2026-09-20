<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dx5-h5-aa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dx5-h5-aa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump-color:spiral-shape" {...props}></Icon>
