<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2e24i0lg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z2e24i0lg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:user-plus" {...props}></Icon>
