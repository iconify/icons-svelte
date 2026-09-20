<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz3q-gb5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="nz3q-gb5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:user-podcast-remix" {...props}></Icon>
