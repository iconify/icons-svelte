<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whx6a7boz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="whx6a7boz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:users-pause" {...props}></Icon>
