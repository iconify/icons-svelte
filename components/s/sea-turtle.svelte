<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_fz9xb-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m_fz9xb-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sea-turtle" {...props}></Icon>
