<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ma_gifbgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ma_gifbgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:volvo-alt" {...props}></Icon>
