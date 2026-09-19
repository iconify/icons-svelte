<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jiqekibzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jiqekibzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:xsl-01" {...props}></Icon>
