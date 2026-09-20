<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5nok1bpn.css';
import '../../css/t/ty41gwbjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b5nok1bpn"/><path class="ty41gwbjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:voidauth-dark" {...props}></Icon>
