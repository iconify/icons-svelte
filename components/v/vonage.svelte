<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/buh5dub3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="buh5dub3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:vonage" {...props}></Icon>
