<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jg5mycc0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jg5mycc0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:triangle-close-fill-round" {...props}></Icon>
