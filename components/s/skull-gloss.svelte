<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c88oob-so.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c88oob-so"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:skull-gloss" {...props}></Icon>
