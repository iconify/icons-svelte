<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kul50ccem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kul50ccem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:textual" {...props}></Icon>
