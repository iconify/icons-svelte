<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxxvhjbvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1920,"height":1536};
const content = `<path class="fxxvhjbvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:tags" {...props}></Icon>
