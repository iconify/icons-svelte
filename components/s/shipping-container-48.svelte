<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ay__5bcmu.css';
import '../../css/f/ff8py9bze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ay__5bcmu"/><path class="ff8py9bze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shipping-container-48" {...props}></Icon>
