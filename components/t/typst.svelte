<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tytcxu7wr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tytcxu7wr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:typst" {...props}></Icon>
