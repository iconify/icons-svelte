<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q86b8g1uw.css';
import '../../css/x/x5qh69bjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q86b8g1uw"/><path clip-rule="evenodd" class="x5qh69bjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:soap-dispenser-droplet-filled" {...props}></Icon>
