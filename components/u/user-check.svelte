<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zx91o1ehl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zx91o1ehl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:user-check" {...props}></Icon>
