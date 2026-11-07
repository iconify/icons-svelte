<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-s5hqb3c.css';
import '../../css/b/bis1pebdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b-s5hqb3c"/><path class="bis1pebdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:shop-minimalistic-outline" {...props}></Icon>
