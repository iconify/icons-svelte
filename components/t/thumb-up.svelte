<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-a4o7b3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-a4o7b3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:thumb-up" {...props}></Icon>
