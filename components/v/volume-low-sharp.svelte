<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yase_ybcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yase_ybcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:volume-low-sharp" {...props}></Icon>
