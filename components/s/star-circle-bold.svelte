<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apl9sq3xl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="apl9sq3xl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:star-circle-bold" {...props}></Icon>
