<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/suih8fnam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="suih8fnam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:sim-card-filled" {...props}></Icon>
