<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4-w59gzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f4-w59gzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:wind-electricity" {...props}></Icon>
