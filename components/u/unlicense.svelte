<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fn1jyeb1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fn1jyeb1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:unlicense" {...props}></Icon>
