<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zya0c2bkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zya0c2bkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:rupee-circle" {...props}></Icon>
