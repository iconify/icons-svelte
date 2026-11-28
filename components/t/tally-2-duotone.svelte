<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvh_n7eff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary qvh_n7eff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:tally-2-duotone" {...props}></Icon>
