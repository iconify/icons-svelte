<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ria7zub2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ria7zub2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:users-search" {...props}></Icon>
