<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5j846b7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r5j846b7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:wavy-warning" {...props}></Icon>
