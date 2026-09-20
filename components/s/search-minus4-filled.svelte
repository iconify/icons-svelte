<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e51u0kr-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e51u0kr-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:search-minus4-filled" {...props}></Icon>
