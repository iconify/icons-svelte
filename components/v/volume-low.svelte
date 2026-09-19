<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dc0n_4bsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dc0n_4bsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:volume-low" {...props}></Icon>
