<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xre4jslvu.css';
import '../../css/w/wq4oxm77o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xre4jslvu"/><path class="wq4oxm77o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:test-tube-bold" {...props}></Icon>
