<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5ux1qk-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c5ux1qk-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:tired" {...props}></Icon>
