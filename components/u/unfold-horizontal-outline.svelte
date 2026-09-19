<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_pu1q0jg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":25};
const content = `<path clip-rule="evenodd" class="i_pu1q0jg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:unfold-horizontal-outline" {...props}></Icon>
