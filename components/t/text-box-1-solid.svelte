<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p540hcswf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="p540hcswf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:text-box-1-solid" {...props}></Icon>
