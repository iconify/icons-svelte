<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3g675bto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="s3g675bto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:transparent-remix" {...props}></Icon>
