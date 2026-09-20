<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6ad6t4cx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f6ad6t4cx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:scrapbox" {...props}></Icon>
