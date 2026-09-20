<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ra2b73bnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ra2b73bnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:source-branch-plus" {...props}></Icon>
