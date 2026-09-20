<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9diafb0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="c9diafb0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:star-medal-solid" {...props}></Icon>
