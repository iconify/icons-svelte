<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zs59oehdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zs59oehdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:screwdriver-fill-round" {...props}></Icon>
