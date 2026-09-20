<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txy-e_bzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="txy-e_bzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:uber-eats" {...props}></Icon>
