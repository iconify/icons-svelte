<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w39xa2bth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="w39xa2bth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:shipping-box-1-remix" {...props}></Icon>
