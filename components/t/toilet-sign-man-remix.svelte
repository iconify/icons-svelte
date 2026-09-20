<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ouhj3-wyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ouhj3-wyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:toilet-sign-man-remix" {...props}></Icon>
