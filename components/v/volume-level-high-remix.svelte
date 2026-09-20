<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l--ug-2eb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="l--ug-2eb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:volume-level-high-remix" {...props}></Icon>
