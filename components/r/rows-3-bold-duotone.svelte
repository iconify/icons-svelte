<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nayqy1c_r.css';
import '../../css/i/ir6vxx7sl.css';
import '../../css/l/lquqiwbln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nayqy1c_r"/><path class="ir6vxx7sl"/><path class="lquqiwbln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rows-3-bold-duotone" {...props}></Icon>
