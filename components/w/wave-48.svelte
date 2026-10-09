<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/voqy8c0sp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="voqy8c0sp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wave-48" {...props}></Icon>
