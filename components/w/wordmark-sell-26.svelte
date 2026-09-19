<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlfb33qbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":33,"height":26};
const content = `<path class="rlfb33qbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:wordmark-sell-26" {...props}></Icon>
