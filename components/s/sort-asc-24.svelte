<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdfbt41fb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kdfbt41fb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:sort-asc-24" {...props}></Icon>
