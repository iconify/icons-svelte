<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2x3ni-gi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d2x3ni-gi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:thumbtack" {...props}></Icon>
