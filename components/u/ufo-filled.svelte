<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9881kbbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o9881kbbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:ufo-filled" {...props}></Icon>
