<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prq4-o15b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="prq4-o15b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:share-2" {...props}></Icon>
