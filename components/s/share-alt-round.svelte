<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxk67cb0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pxk67cb0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:share-alt-round" {...props}></Icon>
