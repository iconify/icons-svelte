<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sk_olrbkj.css';
import '../../css/w/wkqj1nbqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sk_olrbkj"/><path class="wkqj1nbqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:upload-cloud-48-bold" {...props}></Icon>
