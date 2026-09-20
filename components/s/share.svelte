<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjx16568o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-5,"top":-5};
const content = `<path class="wjx16568o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:share" {...props}></Icon>
