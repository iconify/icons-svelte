<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dn-rk_b9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dn-rk_b9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:sidebar2-filled" {...props}></Icon>
