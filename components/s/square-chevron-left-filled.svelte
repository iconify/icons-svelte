<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iae1v6etf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iae1v6etf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-chevron-left-filled" {...props}></Icon>
