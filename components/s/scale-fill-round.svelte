<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qi028cczs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qi028cczs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:scale-fill-round" {...props}></Icon>
