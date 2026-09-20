<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5eeapbuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b5eeapbuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:stair-stepper-fill" {...props}></Icon>
