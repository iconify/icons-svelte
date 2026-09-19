<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iws4iub9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="iws4iub9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:square" {...props}></Icon>
