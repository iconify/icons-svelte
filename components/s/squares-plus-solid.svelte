<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ardha2bkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ardha2bkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:squares-plus-solid" {...props}></Icon>
