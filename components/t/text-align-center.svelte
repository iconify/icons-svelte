<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1d8ngb4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j1d8ngb4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:text-align-center" {...props}></Icon>
