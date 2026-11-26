<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qiok80bhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qiok80bhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="xero-emoji:zzz" {...props}></Icon>
