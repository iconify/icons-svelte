<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnc0q-9gr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="jnc0q-9gr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:sling" {...props}></Icon>
