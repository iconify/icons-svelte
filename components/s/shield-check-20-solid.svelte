<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixh097b2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ixh097b2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:shield-check-20-solid" {...props}></Icon>
