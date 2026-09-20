<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fs5wqyzfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fs5wqyzfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-search-line" {...props}></Icon>
