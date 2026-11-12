<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0jojrbyn.css';
import '../../css/k/kb_awpb0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b0jojrbyn"/><path class="kb_awpb0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:zrok-dark" {...props}></Icon>
