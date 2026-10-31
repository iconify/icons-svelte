<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apr2eo5qt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="apr2eo5qt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:user-round" {...props}></Icon>
