<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/md3vheezs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":384};
const content = `<path class="md3vheezs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:sass" {...props}></Icon>
