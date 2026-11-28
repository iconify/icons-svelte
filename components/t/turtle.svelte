<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6ut-97jv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s6ut-97jv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:turtle" {...props}></Icon>
