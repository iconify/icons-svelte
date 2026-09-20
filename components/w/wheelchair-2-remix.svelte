<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7nsjzbgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="x7nsjzbgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:wheelchair-2-remix" {...props}></Icon>
