<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1cc8abnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c1cc8abnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:star-expressive" {...props}></Icon>
