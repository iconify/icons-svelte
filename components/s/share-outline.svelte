<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bk_0u7b-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bk_0u7b-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:share-outline" {...props}></Icon>
