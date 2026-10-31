<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zyljurtoy.css';
import '../../css/b/bqclo9bhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zyljurtoy"/><path class="bqclo9bhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:siren-off-filled" {...props}></Icon>
