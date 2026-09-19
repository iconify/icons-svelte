<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iihkrub1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iihkrub1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:text-clear-format" {...props}></Icon>
