<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mamrtwaav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mamrtwaav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:separator" {...props}></Icon>
