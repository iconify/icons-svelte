<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q53v49bkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q53v49bkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:search-plus" {...props}></Icon>
