<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4p5vacnv.css';
import '../../css/v/v1l1tsapd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j4p5vacnv"/><path class="v1l1tsapd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:shield-check-duotone" {...props}></Icon>
