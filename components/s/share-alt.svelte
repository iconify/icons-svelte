<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2ru2_b2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v2ru2_b2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:share-alt" {...props}></Icon>
