<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpgbx2bsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tpgbx2bsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:shade-rchiileea-v1" {...props}></Icon>
