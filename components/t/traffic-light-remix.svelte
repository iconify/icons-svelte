<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfv5b7b-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="gfv5b7b-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:traffic-light-remix" {...props}></Icon>
