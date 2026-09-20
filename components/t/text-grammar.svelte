<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzufplyuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zzufplyuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:text-grammar" {...props}></Icon>
