<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ux6p4ubfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ux6p4ubfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:shield-x-mark-solid" {...props}></Icon>
