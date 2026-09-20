<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xh-7kfbgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xh-7kfbgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:slash-fill" {...props}></Icon>
