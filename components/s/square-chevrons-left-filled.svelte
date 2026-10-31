<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5i5bibik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c5i5bibik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-chevrons-left-filled" {...props}></Icon>
