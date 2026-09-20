<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/venf5ntdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="venf5ntdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:wilderness-hut-14" {...props}></Icon>
