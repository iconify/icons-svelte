<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwnd97ges.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uwnd97ges"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wineglass-line" {...props}></Icon>
