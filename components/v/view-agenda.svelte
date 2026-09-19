<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1kqg3xar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f1kqg3xar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:view-agenda" {...props}></Icon>
