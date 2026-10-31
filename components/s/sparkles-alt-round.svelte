<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmck85i-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pmck85i-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:sparkles-alt-round" {...props}></Icon>
