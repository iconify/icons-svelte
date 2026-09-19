<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/act7ucptf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="act7ucptf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:trello" {...props}></Icon>
