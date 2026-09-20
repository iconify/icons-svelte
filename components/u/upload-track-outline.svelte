<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pn8oriblq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pn8oriblq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:upload-track-outline" {...props}></Icon>
