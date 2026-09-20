<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zeofr7ors.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zeofr7ors"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:table-search" {...props}></Icon>
