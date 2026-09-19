<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrai_n05g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hrai_n05g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:text-align-justify-left" {...props}></Icon>
