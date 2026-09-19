<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nunwyac9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nunwyac9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:wifi-off-02" {...props}></Icon>
