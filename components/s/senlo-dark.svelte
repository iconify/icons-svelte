<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idolizczw.css';
import '../../css/d/dhkr_wblc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="idolizczw"/><path class="dhkr_wblc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:senlo-dark" {...props}></Icon>
