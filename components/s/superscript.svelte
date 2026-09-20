<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmmot_bhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jmmot_bhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:superscript" {...props}></Icon>
