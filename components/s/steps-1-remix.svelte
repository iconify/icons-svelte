<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmv-ntbtx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="qmv-ntbtx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:steps-1-remix" {...props}></Icon>
