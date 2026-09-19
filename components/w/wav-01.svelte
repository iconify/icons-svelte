<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyrdbnm5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nyrdbnm5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:wav-01" {...props}></Icon>
