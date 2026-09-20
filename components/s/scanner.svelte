<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bktczq_kz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bktczq_kz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:scanner" {...props}></Icon>
