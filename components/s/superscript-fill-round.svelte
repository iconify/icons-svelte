<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/my5tmi8qa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="my5tmi8qa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:superscript-fill-round" {...props}></Icon>
