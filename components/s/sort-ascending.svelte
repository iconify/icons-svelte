<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcvha2kxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wcvha2kxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:sort-ascending" {...props}></Icon>
