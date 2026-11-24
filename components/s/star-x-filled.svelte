<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/se_pfbimu.css';
import '../../css/n/n4qsi-ucz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="se_pfbimu"/><path class="n4qsi-ucz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:star-x-filled" {...props}></Icon>
