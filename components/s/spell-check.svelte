<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpx7y9xrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kpx7y9xrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:spell-check" {...props}></Icon>
