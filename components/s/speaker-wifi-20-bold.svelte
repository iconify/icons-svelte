<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nb8q1pmkh.css';
import '../../css/s/suvwyfb8m.css';
import '../../css/v/v57n--bcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nb8q1pmkh"/><path class="suvwyfb8m"/><path class="v57n--bcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:speaker-wifi-20-bold" {...props}></Icon>
