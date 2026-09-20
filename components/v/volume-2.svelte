<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lddgidbys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lddgidbys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:volume-2" {...props}></Icon>
