<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3oj0qnnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a3oj0qnnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:vertical-slider-2" {...props}></Icon>
