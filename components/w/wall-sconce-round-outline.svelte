<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qq42mz18t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qq42mz18t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wall-sconce-round-outline" {...props}></Icon>
