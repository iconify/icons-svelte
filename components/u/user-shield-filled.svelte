<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k83am1-wg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k83am1-wg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:user-shield-filled" {...props}></Icon>
