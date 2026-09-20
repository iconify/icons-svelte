<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6c-dln6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q6c-dln6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:space-key" {...props}></Icon>
