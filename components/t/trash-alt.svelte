<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jci4y6a-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jci4y6a-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:trash-alt" {...props}></Icon>
