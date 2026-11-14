<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svidcsblb.css';
import '../../css/v/v744t56bw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="svidcsblb"/><path class="v744t56bw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:voidauth-dark" {...props}></Icon>
