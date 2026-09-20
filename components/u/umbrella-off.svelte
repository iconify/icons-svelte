<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhp1ik06l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nhp1ik06l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:umbrella-off" {...props}></Icon>
