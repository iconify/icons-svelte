<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tv6doabyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tv6doabyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:running-round-outline" {...props}></Icon>
