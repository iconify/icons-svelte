<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbs71wbyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kbs71wbyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:share-ios" {...props}></Icon>
