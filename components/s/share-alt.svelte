<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7aszsb3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p7aszsb3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:share-alt" {...props}></Icon>
