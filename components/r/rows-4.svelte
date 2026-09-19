<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y39o-1t2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y39o-1t2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:rows-4" {...props}></Icon>
