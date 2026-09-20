<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnbjt-bms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="jnbjt-bms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:text-shadow-remix" {...props}></Icon>
