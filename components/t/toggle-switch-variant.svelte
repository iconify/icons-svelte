<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnbl065fr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tnbl065fr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:toggle-switch-variant" {...props}></Icon>
