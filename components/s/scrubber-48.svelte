<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eumvrmloj.css';
import '../../css/o/on432c78a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="eumvrmloj"/><path class="on432c78a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:scrubber-48" {...props}></Icon>
