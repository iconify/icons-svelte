<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3mt7fwhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v3mt7fwhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:skip-next-solid" {...props}></Icon>
