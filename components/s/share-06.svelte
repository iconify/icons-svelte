<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbx2oobum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zbx2oobum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:share-06" {...props}></Icon>
