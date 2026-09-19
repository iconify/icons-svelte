<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jelrnxb9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jelrnxb9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:share-fill" {...props}></Icon>
