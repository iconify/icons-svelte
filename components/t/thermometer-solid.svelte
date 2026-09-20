<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zo5hpmgny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="zo5hpmgny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:thermometer-solid" {...props}></Icon>
