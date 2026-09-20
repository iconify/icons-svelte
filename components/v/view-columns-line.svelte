<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6q8vjbqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a6q8vjbqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:view-columns-line" {...props}></Icon>
