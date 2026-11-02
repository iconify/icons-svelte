<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krlfzsbfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="krlfzsbfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:trunk-fill" {...props}></Icon>
