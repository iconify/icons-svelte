<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_n7oxbfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a_n7oxbfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:volume-2" {...props}></Icon>
