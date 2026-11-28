<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zi8346r3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zi8346r3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:smart-home-x" {...props}></Icon>
