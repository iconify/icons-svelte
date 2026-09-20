<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fn2-zcb5a.css';
import '../../css/h/hx140-n7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="fn2-zcb5a"/><path class="hx140-n7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:yubal" {...props}></Icon>
