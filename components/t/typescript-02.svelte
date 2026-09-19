<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1_ibvt6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p1_ibvt6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:typescript-02" {...props}></Icon>
