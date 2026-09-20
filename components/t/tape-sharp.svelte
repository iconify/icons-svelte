<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hydbs_uyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hydbs_uyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:tape-sharp" {...props}></Icon>
