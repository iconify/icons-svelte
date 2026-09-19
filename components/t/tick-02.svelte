<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5lhpybwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m5lhpybwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:tick-02" {...props}></Icon>
