<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tr44fb1gq.css';
import '../../css/n/n9mo1oxei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tr44fb1gq"/><path class="n9mo1oxei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:tape" {...props}></Icon>
