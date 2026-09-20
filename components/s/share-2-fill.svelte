<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wsgpmlo2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wsgpmlo2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:share-2-fill" {...props}></Icon>
