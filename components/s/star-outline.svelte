<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1t1913vp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r1t1913vp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:star-outline" {...props}></Icon>
