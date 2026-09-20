<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lz9r1ynfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lz9r1ynfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-arrow-right-down-bold" {...props}></Icon>
