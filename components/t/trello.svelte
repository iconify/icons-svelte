<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2i32kysp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b2i32kysp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:trello" {...props}></Icon>
