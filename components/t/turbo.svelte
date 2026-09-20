<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnhwnqbck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dnhwnqbck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:turbo" {...props}></Icon>
