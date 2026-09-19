<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qkb-0tb9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qkb-0tb9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:skip-back-outline" {...props}></Icon>
