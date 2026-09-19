<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/su8br7b-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="su8br7b-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:woman-outline" {...props}></Icon>
