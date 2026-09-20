<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1urtovyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p1urtovyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:trmnl" {...props}></Icon>
