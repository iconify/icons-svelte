<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/py1a31bxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="py1a31bxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:star-outline" {...props}></Icon>
