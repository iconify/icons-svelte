<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ay5dbdcag.css';
import '../../css/t/twhnk8blw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ay5dbdcag"/><path clip-rule="evenodd" class="twhnk8blw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:stretching-round-bold" {...props}></Icon>
