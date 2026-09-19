<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wzc7i60gn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wzc7i60gn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:snow" {...props}></Icon>
