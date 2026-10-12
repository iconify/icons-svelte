<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qskiz0blw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qskiz0blw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:spline-filled" {...props}></Icon>
