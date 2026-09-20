<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x57bw-n-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x57bw-n-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:vegas" {...props}></Icon>
