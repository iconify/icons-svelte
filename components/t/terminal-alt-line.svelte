<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqih82bde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aqih82bde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:terminal-alt-line" {...props}></Icon>
