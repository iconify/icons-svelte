<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_bs3g73h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="m_bs3g73h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:wallet-alt-outline" {...props}></Icon>
