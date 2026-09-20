<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8q1dggjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a8q1dggjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:search-2-list" {...props}></Icon>
