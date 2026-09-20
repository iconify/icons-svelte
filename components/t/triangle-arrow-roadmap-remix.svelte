<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjr0-jbmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qjr0-jbmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:triangle-arrow-roadmap-remix" {...props}></Icon>
