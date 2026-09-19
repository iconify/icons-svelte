<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbs-nk3gx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cbs-nk3gx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:satellite-alt-outlined" {...props}></Icon>
