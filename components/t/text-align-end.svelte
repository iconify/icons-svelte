<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f24ezrl3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f24ezrl3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:text-align-end" {...props}></Icon>
