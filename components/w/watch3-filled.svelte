<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohqg1ybsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ohqg1ybsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:watch3-filled" {...props}></Icon>
