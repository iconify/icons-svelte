<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6spf_kyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f6spf_kyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:tuya" {...props}></Icon>
