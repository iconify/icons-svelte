<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_f4b-ban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w_f4b-ban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:share" {...props}></Icon>
