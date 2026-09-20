<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfrv3tbut.css';
import '../../css/v/vzh-lybal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mfrv3tbut"/><path class="vzh-lybal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sonarr-dark" {...props}></Icon>
