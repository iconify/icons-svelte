<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qph_4msfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qph_4msfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:victory-finger-02" {...props}></Icon>
