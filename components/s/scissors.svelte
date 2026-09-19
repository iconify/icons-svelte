<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2ia2bbar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q2ia2bbar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:scissors" {...props}></Icon>
