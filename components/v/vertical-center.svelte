<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-e5l_3bn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w-e5l_3bn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:vertical-center" {...props}></Icon>
