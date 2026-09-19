<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyu5pxbvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iyu5pxbvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:smoking-filled" {...props}></Icon>
