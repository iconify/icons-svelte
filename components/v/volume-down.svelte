<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/at1_iwbxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="at1_iwbxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:volume-down" {...props}></Icon>
