<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abb0r2bas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="abb0r2bas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:stopwatch-half-remix" {...props}></Icon>
