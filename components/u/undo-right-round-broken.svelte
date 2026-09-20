<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vn7zg8bmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vn7zg8bmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:undo-right-round-broken" {...props}></Icon>
