<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihh-fxb0c.css';
import '../../css/x/xt343bbpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="ihh-fxb0c"/><path class="xt343bbpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:train-alt" {...props}></Icon>
