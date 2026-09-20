<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1se23bda.css';
import '../../css/v/v0_257bnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g1se23bda"/><path class="v0_257bnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wiredoor-dark" {...props}></Icon>
