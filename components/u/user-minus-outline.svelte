<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vob1vf30q.css';
import '../../css/s/sgs7697ri.css';
import '../../css/v/vr5_q7bwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vob1vf30q"/><path class="sgs7697ri"/><path clip-rule="evenodd" class="vr5_q7bwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:user-minus-outline" {...props}></Icon>
