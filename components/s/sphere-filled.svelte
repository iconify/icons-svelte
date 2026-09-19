<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_wn20u3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n_wn20u3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:sphere-filled" {...props}></Icon>
