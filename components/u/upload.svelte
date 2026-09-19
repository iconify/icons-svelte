<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ge0s0ukhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ge0s0ukhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:upload" {...props}></Icon>
