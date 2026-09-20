<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwkg_cb9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mwkg_cb9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:traffic-filled" {...props}></Icon>
