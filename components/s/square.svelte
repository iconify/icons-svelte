<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9ptvdcsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="w9ptvdcsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:square" {...props}></Icon>
