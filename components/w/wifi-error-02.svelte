<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_bccvbch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_bccvbch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:wifi-error-02" {...props}></Icon>
