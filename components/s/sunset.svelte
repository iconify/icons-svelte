<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btymlwd6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="btymlwd6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:sunset" {...props}></Icon>
