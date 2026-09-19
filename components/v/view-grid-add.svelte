<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gh_c81byh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gh_c81byh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:view-grid-add" {...props}></Icon>
