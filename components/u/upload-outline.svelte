<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpkyes8mm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bpkyes8mm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:upload-outline" {...props}></Icon>
