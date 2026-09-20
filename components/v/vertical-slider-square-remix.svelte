<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ag3297hsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ag3297hsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:vertical-slider-square-remix" {...props}></Icon>
