<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pd2d9rhru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pd2d9rhru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tooth-48" {...props}></Icon>
