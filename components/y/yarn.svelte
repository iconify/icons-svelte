<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vh7ouzyov.css';
import '../../css/l/l14k1ybbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vh7ouzyov"/><path clip-rule="evenodd" class="l14k1ybbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:yarn" {...props}></Icon>
