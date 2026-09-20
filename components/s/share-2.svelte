<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lui9wgb9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lui9wgb9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:share-2" {...props}></Icon>
