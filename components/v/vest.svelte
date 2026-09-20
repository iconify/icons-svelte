<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc62ocbyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lc62ocbyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:vest" {...props}></Icon>
