<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iuti-oq0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="iuti-oq0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:square-large-outline" {...props}></Icon>
