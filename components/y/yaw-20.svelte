<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oywa71ble.css';
import '../../css/v/vf-xpzeqo.css';
import '../../css/k/ko9sw4b7p.css';
import '../../css/t/tnrvi8b7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oywa71ble"/><path class="vf-xpzeqo"/><path class="ko9sw4b7p"/><path class="tnrvi8b7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:yaw-20" {...props}></Icon>
