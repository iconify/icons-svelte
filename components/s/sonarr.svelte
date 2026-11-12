<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt2kvac7n.css';
import '../../css/p/phq-p1_xp.css';
import '../../css/p/pnsl0jbnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dt2kvac7n"/><path class="phq-p1_xp"/><path class="pnsl0jbnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sonarr" {...props}></Icon>
