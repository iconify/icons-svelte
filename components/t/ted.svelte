<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfcc52b_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bfcc52b_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ted" {...props}></Icon>
