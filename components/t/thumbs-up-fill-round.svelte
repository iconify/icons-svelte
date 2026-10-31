<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqapvxbrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jqapvxbrn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:thumbs-up-fill-round" {...props}></Icon>
