<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6y2bzbhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x6y2bzbhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:user-03" {...props}></Icon>
