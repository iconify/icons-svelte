<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8z5n0tle.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="n8z5n0tle"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:star-circle-remix" {...props}></Icon>
