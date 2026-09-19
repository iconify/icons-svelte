<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azp8fbcgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="azp8fbcgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:sun-drizzle" {...props}></Icon>
