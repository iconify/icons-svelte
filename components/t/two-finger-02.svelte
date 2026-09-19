<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3r5gmb5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y3r5gmb5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:two-finger-02" {...props}></Icon>
