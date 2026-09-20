<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddo040ffb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ddo040ffb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:siren-sharp" {...props}></Icon>
