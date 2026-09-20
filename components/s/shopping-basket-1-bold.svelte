<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hj24m_bxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hj24m_bxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:shopping-basket-1-bold" {...props}></Icon>
