<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qm-7o-8hm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qm-7o-8hm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:user-unlocked" {...props}></Icon>
