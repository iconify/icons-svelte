<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vp1q85cys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vp1q85cys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:unlink-24" {...props}></Icon>
