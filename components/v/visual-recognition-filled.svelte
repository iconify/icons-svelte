<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfwmerbfq.css';
import '../../css/z/zbqhemi-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zfwmerbfq"/><path class="zbqhemi-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:visual-recognition-filled" {...props}></Icon>
