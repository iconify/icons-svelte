<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdeum2vmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bdeum2vmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:share-2-light" {...props}></Icon>
