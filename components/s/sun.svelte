<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ci-09np2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ci-09np2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:sun" {...props}></Icon>
