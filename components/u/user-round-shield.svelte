<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plpgm1gvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="plpgm1gvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:user-round-shield" {...props}></Icon>
