<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knztfskjt.css';
import '../../css/p/p-38xzm7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="knztfskjt"/><path class="p-38xzm7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ticc-dash" {...props}></Icon>
