<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4cg5bcvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="g4cg5bcvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:thermometer-digital" {...props}></Icon>
