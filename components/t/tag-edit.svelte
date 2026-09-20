<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3b3-73sw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v3b3-73sw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tag-edit" {...props}></Icon>
