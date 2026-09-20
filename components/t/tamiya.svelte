<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwidfkbqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rwidfkbqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:tamiya" {...props}></Icon>
