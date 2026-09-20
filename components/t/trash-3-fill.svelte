<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_rp64b0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m_rp64b0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:trash-3-fill" {...props}></Icon>
