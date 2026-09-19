<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uy398my-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uy398my-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:zoom-out-fill" {...props}></Icon>
