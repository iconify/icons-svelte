<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crvcl9i5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="crvcl9i5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:vauxhall" {...props}></Icon>
