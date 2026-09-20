<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ka611bb2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ka611bb2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:shop-outline" {...props}></Icon>
