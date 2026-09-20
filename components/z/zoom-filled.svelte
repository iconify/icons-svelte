<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k188_hbnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k188_hbnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:zoom-filled" {...props}></Icon>
