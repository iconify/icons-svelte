<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncnv5zbty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ncnv5zbty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:virus-24px" {...props}></Icon>
