<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vve2ttzer.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vve2ttzer"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:sort-arrow-light" {...props}></Icon>
