<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udet_s4_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="udet_s4_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:water-glass-filled" {...props}></Icon>
