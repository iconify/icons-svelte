<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9q1o4bfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e9q1o4bfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:shield-warning-fill-round" {...props}></Icon>
