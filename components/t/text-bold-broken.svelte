<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gflkqcblb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gflkqcblb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:text-bold-broken" {...props}></Icon>
