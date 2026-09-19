<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1b1yq60o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="a1b1yq60o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:square-large" {...props}></Icon>
