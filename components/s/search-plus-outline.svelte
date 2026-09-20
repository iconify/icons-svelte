<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sy-k-4nua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sy-k-4nua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:search-plus-outline" {...props}></Icon>
