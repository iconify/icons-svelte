<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqf7kkdmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tqf7kkdmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:table-x" {...props}></Icon>
