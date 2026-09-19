<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlfi_1iqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rlfi_1iqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:secure-data" {...props}></Icon>
