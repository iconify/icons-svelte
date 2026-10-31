<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uyy8nwb5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uyy8nwb5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:text-align-left-round" {...props}></Icon>
