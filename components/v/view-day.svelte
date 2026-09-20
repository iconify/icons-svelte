<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uc_jdi2hk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uc_jdi2hk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:view-day" {...props}></Icon>
