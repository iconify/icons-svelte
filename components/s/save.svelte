<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6swucc0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x6swucc0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:save" {...props}></Icon>
