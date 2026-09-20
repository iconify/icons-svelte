<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdipvbb3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sdipvbb3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:wave-saw-tool" {...props}></Icon>
