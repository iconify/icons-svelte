<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qeb7o8bgl.css';
import '../../css/p/phq-p1_xp.css';
import '../../css/t/t12_olc7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qeb7o8bgl"/><path class="phq-p1_xp"/><path class="t12_olc7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sonarr" {...props}></Icon>
