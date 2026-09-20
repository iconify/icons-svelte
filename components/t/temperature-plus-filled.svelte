<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thukg2blq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="thukg2blq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:temperature-plus-filled" {...props}></Icon>
