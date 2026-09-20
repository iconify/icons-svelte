<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvaty4zot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fvaty4zot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:scenery" {...props}></Icon>
