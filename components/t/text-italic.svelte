<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uakjzi8de.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uakjzi8de"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:text-italic" {...props}></Icon>
