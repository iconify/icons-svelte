<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfae7sbqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="mfae7sbqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:wechat-small-filled" {...props}></Icon>
