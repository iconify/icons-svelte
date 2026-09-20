<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnhapac5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vnhapac5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-share-line-outline" {...props}></Icon>
