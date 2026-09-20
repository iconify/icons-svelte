<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kke7zvbsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kke7zvbsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:sort-ascending-2-filled" {...props}></Icon>
