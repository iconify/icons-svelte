<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ex6_f7bqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ex6_f7bqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:vauxhall" {...props}></Icon>
