<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ic7rc9bjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ic7rc9bjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:shrink-right" {...props}></Icon>
