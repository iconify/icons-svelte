<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u87sqsbpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="u87sqsbpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:text-shadow-solid" {...props}></Icon>
