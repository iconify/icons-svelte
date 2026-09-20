<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7x_debjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e7x_debjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:speaker-deck" {...props}></Icon>
