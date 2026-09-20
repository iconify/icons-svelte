<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7npn_d3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="d7npn_d3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:treasure-chest-remix" {...props}></Icon>
