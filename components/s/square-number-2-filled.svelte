<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lk6_zlb3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lk6_zlb3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-number-2-filled" {...props}></Icon>
